<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt_rr58_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jt_rr58_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:templ" {...props}></Icon>
