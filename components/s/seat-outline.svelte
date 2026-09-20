<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck7do9bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck7do9bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-outline" {...props}></Icon>
