<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/iaoomgb7e.css';
import '../../css/k/kvh9upbae.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2m4WoNWP"><g class="v3_i3wktz"><path class="iaoomgb7e"/><path class="kvh9upbae"/></g></mask></defs><path mask="url(#SVG2m4WoNWP)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tag" {...props}></Icon>
