<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adexpl72i.css';
import '../../css/r/r8cyu3bwz.css';
import '../../css/c/c-oefac8g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXTysScpk"><g class="adexpl72i"><rect class="r8cyu3bwz"/><rect class="c-oefac8g"/></g></mask></defs><path mask="url(#SVGXTysScpk)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:zero-key" {...props}></Icon>
