---
title: コントロール パネルのベンダーとパートナー センターへの登録 |パートナー センター
ms.topic: article
ms.date: 12/11/2018
Description: How to enroll in Partner Center as a Control Panel Vendor
author: labrenne
ms.author: labrenne
keywords: コントロール パネルのベンダー、CPV アプリの登録、CPV アプリを管理します。
ms.localizationpriority: medium
ms.openlocfilehash: 47c404c7620d66cecb1dcb1572a7c8ac85d17261
ms.sourcegitcommit: 98bcceea95b8d9ee5d386456a723f0b8da3ebd58
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/17/2018
ms.locfileid: "8972129"
---
# <a name="enroll-in-partner-center-as-a-control-panel-vendor"></a><span data-ttu-id="2f5a2-103">パートナー センターで、コントロール パネルのベンダーとして登録します。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-103">Enroll in Partner Center as a Control Panel Vendor</span></span>

**<span data-ttu-id="2f5a2-104">適用対象</span><span class="sxs-lookup"><span data-stu-id="2f5a2-104">Applies to</span></span>**

- <span data-ttu-id="2f5a2-105">パートナー センター</span><span class="sxs-lookup"><span data-stu-id="2f5a2-105">Partner Center</span></span>

<span data-ttu-id="2f5a2-106">コントロール パネル ベンダー (CPV) は、有効にすると、パートナー センター Api と統合して、システムにクラウド ソリューション プロバイダー (CSP) パートナーで使用するアプリケーションを開発している、独立系ソフトウェア ベンダーです。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-106">A Control Panel Vendor (CPV) is an independent software vendor that develops applications for use by Cloud Solution Provider (CSP) partners to enable them to integrate their systems with Partner Center APIs.</span></span> <span data-ttu-id="2f5a2-107">コントロール パネルのベンダーは、パートナー センター ダッシュ ボードに直接アクセスできる、CSP パートナーまたはパートナー センター Api ではありません。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-107">A Control Panel vendor is not a CSP Partner with direct access to the Partner Center dashboard or Partner Center APIs.</span></span>

<span data-ttu-id="2f5a2-108">現在のコントロール パネル ベンダー (CPV) またはマイクロソフトのパートナーと連携する新しい CPV であるかどうか Microsoft できるようになりましたする必要があります、アプリケーションを登録し、クラウド ソリューション プロバイダー パートナーをサポートするためにパートナー センターに登録します。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-108">Whether you are a current Control Panel Vendor (CPV) or a new CPV who wants to work with Microsoft partners, Microsoft now requires you to enroll in Partner Center in order to register your applications and support Cloud Solution Provider partners.</span></span> <span data-ttu-id="2f5a2-109">アカウントを作成するには、CPV パートナーは、既存の CSP パートナー テナント、または既存の CPV テナントを使用できますか、オンボード プロセスの一環として新しいテナントを作成することができます。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-109">To create an account, a CPV partner can either use an existing CSP partner tenant, or existing CPV tenant or can create a new tenant as part of onboarding process.</span></span> <span data-ttu-id="2f5a2-110">CPV パートナーは、既存の CSP テナントの使用を選択して場合、は、別のマルチ テナント アプリケーションを作成し、それらをパートナー センターで CPV アクティビティの登録に必要ありますが。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-110">If the CPV partner chooses to use the existing CSP tenant, then they’ll need to create separate multi-tenant applications and register them in Partner Center for CPV activities.</span></span> <span data-ttu-id="2f5a2-111">アプリケーションは、CSP と CPV の両方のアプリケーションとして登録することはできません。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-111">An application can’t be registered as both a CSP and CPV application.</span></span> <span data-ttu-id="2f5a2-112">パートナー センターに登録されているし、アプリケーションが登録されているが、パートナー センター Api へのアクセスがあります。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-112">After you have enrolled in Partner Center and registered your applications, you will have access to the Partner Center APIs.</span></span>  <span data-ttu-id="2f5a2-113">Microsoft は、サンド ボックスの情報を使ってパートナー センターの通知で連絡します。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-113">Microsoft will contact you via a Partner Center notification with your sandbox information.</span></span> <span data-ttu-id="2f5a2-114">ただし、既にサンド ボックス アカウントがある場合は、引き続き使用できます。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-114">If, however, you already have a sandbox account, continue using it.</span></span> <span data-ttu-id="2f5a2-115">新しいサンド ボックスは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-115">You won’t need a new sandbox.</span></span>   


## <a name="working-in-partner-center"></a><span data-ttu-id="2f5a2-116">パートナー センターで作業</span><span class="sxs-lookup"><span data-stu-id="2f5a2-116">Working in Partner Center</span></span>
<span data-ttu-id="2f5a2-117">パートナー センター CPV エクスペリエンスに登録されているし、受け入れ CPV 契約をすることができます。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-117">Once you have enrolled in the Partner Center CPV experience and accepted the CPV agreement you can:</span></span>

- <span data-ttu-id="2f5a2-118">(Azure portal では、アプリケーションの登録し、パートナー センターでのアプリケーションの登録を解除の追加) マルチ テナント アプリケーションを管理します。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-118">Manage multi-tenant applications (add applications to Azure portal, register and unregister applications in Partner Center).</span></span>

>[!Note] 
><span data-ttu-id="2f5a2-119">CPVs は、パートナー センター Api の権限を取得するために、パートナー センターでアプリケーションを登録する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-119">CPVs must register their applications in Partner Center in order to get authorized for Partner Center APIs.</span></span> <span data-ttu-id="2f5a2-120">アプリケーションだけで、Azure ポータルを追加する場合、パートナー センター api CPV アプリケーションは承認されません。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-120">Adding applications to the Azure portal alone does not authorize CPV applications for Partner Center APIs.</span></span> 

- <span data-ttu-id="2f5a2-121">表示し、CPV プロファイルの管理</span><span class="sxs-lookup"><span data-stu-id="2f5a2-121">View and manage your CPV profile</span></span> 

- <span data-ttu-id="2f5a2-122">表示および CPV 機能へのアクセスを必要とするユーザーを管理します。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-122">View and manage your users who need access to CPV capabilities.</span></span> <span data-ttu-id="2f5a2-123">唯一の役割、CPV ことができますがグローバル管理者です。</span><span class="sxs-lookup"><span data-stu-id="2f5a2-123">The only role a CPV can have is global admin.</span></span>

