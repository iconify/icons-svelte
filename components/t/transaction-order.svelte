<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/c/cwi9jf16v.css';
import '../../css/h/hhy6b2bre.css';
import '../../css/k/kikd_09-e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGb9GG3dpr"><g class="ufeehvblu"><rect class="cwi9jf16v"/><path class="hhy6b2bre"/><path class="kikd_09-e"/></g></mask></defs><path mask="url(#SVGb9GG3dpr)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:transaction-order" {...props}></Icon>
