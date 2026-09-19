<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/k/ktokpccng.css';
import '../../css/r/rtdu8kbun.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6EkOAb1c"><g class="ufeehvblu"><path class="ktokpccng"/><path class="rtdu8kbun"/></g></mask></defs><path mask="url(#SVG6EkOAb1c)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:watermelon" {...props}></Icon>
