<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk6fjp9qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk6fjp9qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:signal-strength-5" {...props}></Icon>
