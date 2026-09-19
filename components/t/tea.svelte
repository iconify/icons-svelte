<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/a/a41kkkbae.css';
import '../../css/y/yokqbnb6v.css';
import '../../css/y/yonyb1bwh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGECfyEcxW"><g class="hv130ab-t"><path class="a41kkkbae"/><path class="yokqbnb6v"/><path class="yonyb1bwh"/></g></mask></defs><path mask="url(#SVGECfyEcxW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tea" {...props}></Icon>
