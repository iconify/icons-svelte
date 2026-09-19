<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di9d21bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="di9d21bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:search" {...props}></Icon>
