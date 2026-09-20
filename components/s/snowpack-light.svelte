<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etyfe9bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":700,"left":-30,"top":-94};
const content = `<path class="etyfe9bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:snowpack-light" {...props}></Icon>
