<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv9a28bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv9a28bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:worm" {...props}></Icon>
