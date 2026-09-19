<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1_swcb_o.css';
import '../../css/d/dwhj-nzls.css';
import '../../css/c/c9_-b0brr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9SKiadwd"><g class="v1_swcb_o"><path class="dwhj-nzls"/><path class="c9_-b0brr"/></g></mask></defs><path mask="url(#SVG9SKiadwd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:youtobe" {...props}></Icon>
