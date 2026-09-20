<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkfpo49xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tkfpo49xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tailwindcss" {...props}></Icon>
