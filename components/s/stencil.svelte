<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul8462u1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ul8462u1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:stencil" {...props}></Icon>
