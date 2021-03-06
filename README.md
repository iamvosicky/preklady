# preklady

projectStatus.CONCEPT=Koncept
projectStatus.APPROVAL=Schvalování
projectStatus.RUNNING=Běžící
projectStatus.CLOSED=Uzavřený
projectStatus.TERMINATED=Ukončený
assignmentStatus.CONCEPT=Koncept
assignmentStatus.ACTIVE=Aktivní
assignmentStatus.CLOSED=Ukončená
timesheetStatus.CONCEPT=Koncept
timesheetStatus.SENT=Odesláno
timesheetStatus.REJECTED=Odmítnuto
timesheetStatus.APPROVED=Schváleno
timesheetStatus.INVOICED=Fakturovaný

entity.assignment=Alokace
entity.project=Projekt
entity.user=Osoba
entity.date=Datum
ASSIGNMENT=Alokace
PROJECT=Projekt
USER=Osoba
error.entity.notFound=Vybraná hodnota nebyla nalezena.
error.entity.attribute.missingPermissions=Vaše oprávnění neumožňuje změnu hodnoty.
error.password.reset.token.validity=Reset token hesla je po expiraci nebo byl již použit.
error.password.reset.token.notFound=Reset token hesla byl již použit.
error.password.validation.regex=Špatný formát (kombinace A-Z a-z 0-9 $@$!%*?&, min 6 znaků)
error.project.name.isEmpty=Název projektu nesmí být prázdný.
error.project.financialType.isEmpty=Finanční typ nesmí být prázdný.
error.project.endDate.isEmpty=Konec projektu nesmí být prázdný.
error.project.startDate.isEmpty=Začátek projektu nesmí být prázdný.
error.project.startDate.afterEndDate=Začátek projektu nesmí být po konci projektu.
error.project.startDate.afterEconomies=Začátek projektu nesmí být po datu platnosti od druhé a dalších baselines.
error.project.financialType.isNotFTFP=Nelze schválit projekt, který není FTFP.
error.project.client.isEmpty=Klient nesmí být prázdný.
error.project.costCenter.isEmpty=Nákladové středisko nesmí být prázdné.
error.project.projectManager.isEmpty=Projektový manažér nesmí být prázdný.
error.project.accountManager.isEmpty=Účetní nesmí být prázdný.
error.project.gr.isEmpty=Hrubý výnos nesmí být prázdný.
error.project.gr.ltZero=Hrubý výnos musí být kladné číslo.
error.project.cogs.isEmpty=Náklady nesmí být prázdné.
error.project.cogs.ltZero=Náklady musí být kladné číslo.
error.project.code.isEmpty=Identifikátor projektu nesmí být prázdný.
error.project.code.doesntMatchRegex=Idenetifikátor projektu má špatný formát.
error.project.code.duplicate=Kód projektu musǐ být unikátní.
error.projectEconomy.validFrom.beforeStart=Datum platnosti od nesmí být před zahájením projektu
error.projectEconomy.validFrom.afterEnd=Datum platnosti od nesmí být po konci projektu
error.projectEconomy.validFrom.existing=Datum platnosti od nesmí být stejné jako jiné datum platnosti od jiné verze baseline
error.projectEconomy.gr.isEmpty=GR nesmí být prázdné
error.projectEconomy.cogs.isEmpty=COGS nesmí být prázdné
validation.project.costCenter.duplicity=Existuje již projekt s tímto nákladovým střediskem.
validation.project.delete.demands=Neuzavřených žádostí - {0}.
validation.project.delete.assignments=Schválených alokací - {0}.
validation.project.delete.timesheets=Schválených/Zaúčtovaných výkazů - {0}.
validation.project.delete.financialExpenses=Zaúčtovaných finančních nákladů - {0}.
validation.project.delete.financialReturns=Zaúčtovaných finančních výnosů - {0}.
validation.projectEconomy.delete.lastEconomy=Nelze smazat poslední baseline projektu.
error.project.name.not10=Název projektu nesmí být 10.
error.timesheet.summary.user.isEmpty=Osoba nesmí být prázdná.
error.timesheet.summary.user.invalid=Nepodařilo se najít osobu.
error.timesheet.summary.date.isEmpty=Datum výkazu nesmí být prázdné.
error.timesheet.summary.date.isAfterNow=Nemožno založit výkaz pro budoucí měsíce.
error.timesheet.summary.date.alreadyExists=Výkaz pro toto období již existuje.
error.timesheet.summary.moreDaysThanPossible=Počet dní převyšuje maximální hodnotu pro daný měsíc.
error.timesheet.summary.invoice.isEmpty=Faktura nesmí být prázdná.
error.timesheet.summary.invoice.invalid=Nepodařilo se najít fakturu.
error.timesheet.reportedTo.isEmpty=Vykázáno na nesmí být prázdné.
error.timesheet.reportedTo.duplicity=Vykázáno na nesmí být duplicitní v daném období.
error.timesheet.assignment.invalid=Nepodařilo se najít alokaci.
error.timesheet.daysWorked.isEmpty=Počet dní nesmí být prázdný.
error.timesheet.daysWorked.isZeroNegative=Počet musí být vyšší než 0.
error.timesheet.daysWorked.isGreaterThan=Nemůžete vytvořit výkaz s více než 100 000 MDs.
error.timesheet.report.isEmpty=U této alokace je soubor povinný.
error.timesheet.report.invalid=Nepodařilo se najít report.
error.timesheet.note.not10=Poznámka nesmí být 10.
error.assignment.project.isEmpty=Projekt nesmí být prázdný.
error.assignment.assignmentEconomy.sellRate.isEmpty=Prodejní sazba nesmí být prázdný.
error.assignment.contracts.isEmpty=Kontrakty nesmí být prázdné.
error.assignment.contracts.user.isEmpty=Osoba musí být vyplněna.
error.assignment.timesheetRequired.isEmpty=Pole "Vyžadovat report" nesmí být prázdné.
error.assignment.startDate.isBeforeProjectStart=U FTFP projektu nesmí alokace začínat před začátkem projektu.
error.assignment.endDate.isAfterProjectEnd=U FTFP projektu nesmí alokace končit po konci projektu.
error.assignment.endDate.timesheets=Po tomto datu existují výkazy (posuňte konec alokace tak, aby zahrnoval všechny výkazy nebo výkazy mimo období alokace odstraňte).
error.assignment.startDate.timesheets=Před tímto datem existují výkazy (posuňte začátek alokace tak, aby zahrnoval všechny výkazy nebo výkazy mimo období alokace odstraňte).
error.assignment.user.timesheets=Nelze změnit osobu, protože k alokaci existují napojené výkazy.
error.assignment.startDate.afterEndDate=Začátek alokace nesmí být po konci alokace.
error.assignment.close.endDate=Při uzavření nemůže být konec alokace v budoucnu.
error.assignment.closed.endDate=V tomto stavu alokace nemůže být datum v budoucnu.
error.assignment.resourceManager.invalid=Resource manager musí být RM u oddělení kontraktů.
error.assignment.timeWork.zeroNegative=Úvazek musí být větší než 0.
error.assignment.allocationLength.zeroNegative=Počet MD musí být větší než 0.
error.assignment.allocationLength.invalidValue=Počet MD musí odpovídat počtu pracovních dní X úvazek.
error.department.name.isEmpty=Název nesmí být prázdný.
error.department.name.duplicity=Název je již použit.
error.department.resourceManagers.isEmpty=Resource manager musí být vyplněn.
error.department.resourceManagers.notResourceManager=Vybraná hodnota nebyla nalezena. Položky v seznamu jsme proto aktualizovali.
error.department.manager.isEmpty=Manager nesmí být prázdný.
error.department.superiorDepartment.cyclingDependency=Zkontrolujte nadřazené oddělení - vznikla cyklická vazba.
error.department.superiorDepartment.invalid=Zkontrolujte nadřazené oddělení - nemůže být sám sobě nadřazeným oddělením.
error.contract.contract.isEmpty=Smlouva nesmí být prázdná.
error.contract.contract.cannotLinkProjects=Pro tento typ smluvního vztahu není možné nastavit vazbu na projekt za účelem fakturování služeb.
error.contract.startDate.isEmpty=Datum zahájení nesmí být prázdné.
error.contract.contractor.isEmpty=Dodavatel nesmí být prázdný.
error.contract.timework.isEmpty=Úvazek nesmí být prázdný.
error.contract.department.isEmpty=Oddělení nesmí být prázdné.
error.contract.resourceManager.isEmpty=Manager nesmí být prázdný.
error.client.delete.projects=Navázaných projektů - \
  .
error.project.delete.assignments=Navázaných alokací - {0}.
error.project.delete.reports=Navázaných reportů - {0}.
error.project.delete.invoices=Navázaných faktur - {0}.
error.project.delete.update.invoices=Navázaných faktur - {0}.
error.project.delete.update.users=Navázaných lidí - {0}.
error.assignment.delete.reports=Navázaných reportů - {0}.
error.timesheet.delete.invoices=Výkaz nelze smazat. Návazná faktura je ve stavu, kdy nemůžete výkaz odstranit.
error.timesheet.delete.update.invoices=Navázaných faktur - {0}.
error.timesheet.update.invoices=Nemůžete upravit výkaz, protože návazné položky jsou ve chráněném stavu - {0}.
error.timesheet.update.invoices.missingPermissions=Nemůžete upravit výkaz, protože návazné položky jsou ve chráněném stavu.
error.timesheet.approve.startDate.assignment=Nelze schválit výkaz, protože termíny alokace nezahrnují měsíc na výkazu.
error.timesheet.invoice.startDate.assignment=Nelze fakturovat výkaz, protože termíny alokace nezahrnují měsíc na výkazu.
error.contract.delete.assignments=Navázaných alokací - {0}.
error.contract.delete.users=Navázaných uživatelů - {0}.
error.contractor.delete.users=Navázaných uživatelů - {0}.
error.projectStatus.delete.projects=Navázaných projektů - {0}.
error.assignmentStatus.delete.assignments=Navázaných alokací - {0}.
error.timesheetStatus.delete.timesheets=Navázaných výkazů - {0}.
timesheet.statuses.concept=Koncept
timesheet.statuses.sent=Odesláno
timesheet.statuses.rejected=Odmítnuto
timesheet.statuses.approved=Schváleno
timesheet.statuses.invoiced=Fakturovaný
timesheet.statuses.deleted=Smazáno
error.file.maxUploadedSize=Překročen limit pro velikost nahrávaného souboru.
error.file.contentType=Špatný typ nahrávaného souboru. Lze nahrát pdf, doc, docx, xls, xlsx, txt, rtf, obrázky.
transition.project.approval=Ke schválení
transition.project.approve=Schválit projekt
transition.project.reject=Odmítnout projekt
transition.project.close=Uzavřít projekt
transition.project.terminate=Ukončit projekt
transition.assignment.accept=Potvrdit
transition.assignment.close=Uzavřít
transition.assignment.restore=Obnovit
transition.assignment.concept=Koncept
transition.timesheet.send=Odeslat
transition.timesheet.approve=Schválit
transition.timesheet.reject=Odmítnout
transition.timesheet.invoice=Fakturovat
transition.timesheet.correct=Opravit
transition.hint.timesheet.reject.title=Zamítnutí výkazu
transition.hint.timesheet.reject.description=Opravdu si přejete zamítnout výkaz?
transition.hint.timesheet.reject.buttonText=Zamítnout
transition.hint.timesheet.reject.actionText=Vlastní důvod
transition.hint.timesheet.reject.additionalHintText=Důvod ze šablony
codetable.assignmentStatus.value.name=Hodnota stavu
codetable.assignmentStatus.color.name=Barva
codetable.assignmentStatus.isApprovalStatus.name=Stav pro potvrzenou alokaci?
codetable.projectStatus.value.name=Hodnota stavu
codetable.client.code.name=Kód
codetable.client.isActive.name=Je aktivní?
codetable.contractor.code.name=IČO
codetable.contractor.isDefault.name=Je výchozí?
codetable.contractor.isActive.name=Je aktivní?
codetable.contractor.managers.name=Manažeři
codetable.contract.contractType.name=Typ kontraktu
codetable.contract.isActive.name=Je aktivní?
codetable.contract.invoiceRequired.name=Faktura povinná?
codetable.timesheetStatus.value.name=Hodnota stavu
