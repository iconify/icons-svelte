<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6a69czjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c6a69czjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:virtual" {...props}></Icon>
