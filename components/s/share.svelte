<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o36r4393d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="o36r4393d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:share" {...props}></Icon>
