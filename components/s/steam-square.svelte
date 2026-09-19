<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf8qucwjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="hf8qucwjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:steam-square" {...props}></Icon>
