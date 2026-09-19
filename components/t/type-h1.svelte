<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di220krrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="di220krrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-h1" {...props}></Icon>
