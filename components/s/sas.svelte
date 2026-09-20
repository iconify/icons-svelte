<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjmigcbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6.35,"height":6.35};
const content = `<path class="cjmigcbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:sas" {...props}></Icon>
