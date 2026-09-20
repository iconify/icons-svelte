<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo8189bjo.css';
import '../../css/v/v0h1tybbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uo8189bjo"/><path clip-rule="evenodd" class="v0h1tybbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:warning-32" {...props}></Icon>
