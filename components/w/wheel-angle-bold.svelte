<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkv2srbts.css';
import '../../css/g/g47xhxbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkv2srbts"/><path clip-rule="evenodd" class="g47xhxbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wheel-angle-bold" {...props}></Icon>
