<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3k5mabfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k3k5mabfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:visualstudio" {...props}></Icon>
