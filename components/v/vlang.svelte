<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsp-aobcy.css';
import '../../css/f/fbai653fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="hsp-aobcy"/><path class="fbai653fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vlang" {...props}></Icon>
