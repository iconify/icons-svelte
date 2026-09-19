<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/b/bm-9awbcn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdziXTd4Z"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="bm-9awbcn"/></g></mask></defs><path mask="url(#SVGdziXTd4Z)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:smiling-face-with-squinting-eyes" {...props}></Icon>
