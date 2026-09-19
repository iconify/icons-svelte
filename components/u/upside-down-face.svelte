<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/hgyipz03i.css';
import '../../css/t/to1q24v3e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNFhCWduG"><g class="v3_i3wktz"><path class="hgyipz03i"/><path class="to1q24v3e"/></g></mask></defs><path mask="url(#SVGNFhCWduG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:upside-down-face" {...props}></Icon>
