<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7rontbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h7rontbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zip" {...props}></Icon>
