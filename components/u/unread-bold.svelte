<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybec0eb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybec0eb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:unread-bold" {...props}></Icon>
