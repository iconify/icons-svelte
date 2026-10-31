<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4qkawp1w.css';
import '../../css/w/woy2hk4bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4qkawp1w"/><path class="woy2hk4bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-shield-filled" {...props}></Icon>
