<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/y91dc7fgl.css';
import '../../css/f/f13g7bbsq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGf1eZDeMa"><g class="v3_i3wktz"><path class="y91dc7fgl"/><path class="f13g7bbsq"/></g></mask></defs><path mask="url(#SVGf1eZDeMa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:thermos-cup" {...props}></Icon>
