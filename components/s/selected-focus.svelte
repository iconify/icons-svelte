<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/d9ti0tfzb.css';
import '../../css/y/ywx-y6bsq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3ChUSdYG"><g class="v3_i3wktz"><path class="d9ti0tfzb"/><path class="ywx-y6bsq"/></g></mask></defs><path mask="url(#SVG3ChUSdYG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:selected-focus" {...props}></Icon>
