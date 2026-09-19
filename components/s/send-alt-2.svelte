<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix5oy4d5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix5oy4d5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:send-alt-2" {...props}></Icon>
