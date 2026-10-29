<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/ka27c-bva.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/n/ncvxbdbpd.css';
import '../../css/q/q294q2b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ka27c-bva wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="ncvxbdbpd"/><path class="q294q2b5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-dashed-blueprint" {...props}></Icon>
