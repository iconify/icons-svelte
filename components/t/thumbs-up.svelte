<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dt8jlkbav.css';
import '../../css/a/afpz-89xh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4Xv1gcFj"><g class="v3_i3wktz"><path class="dt8jlkbav"/><path class="afpz-89xh"/></g></mask></defs><path mask="url(#SVG4Xv1gcFj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:thumbs-up" {...props}></Icon>
