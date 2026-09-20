<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_dr6cb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_dr6cb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tcl" {...props}></Icon>
