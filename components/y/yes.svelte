<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txo7vqb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="txo7vqb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:yes" {...props}></Icon>
