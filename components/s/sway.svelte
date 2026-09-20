<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfhguzbcb.css';
import '../../css/f/f_mc5ezfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jfhguzbcb"/><path class="f_mc5ezfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:sway" {...props}></Icon>
