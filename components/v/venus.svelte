<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv9y25q_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv9y25q_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:venus" {...props}></Icon>
