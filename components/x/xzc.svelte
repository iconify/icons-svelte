<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du7r8ebju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="du7r8ebju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xzc" {...props}></Icon>
