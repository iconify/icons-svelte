<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkv3urbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkv3urbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:support-ai" {...props}></Icon>
