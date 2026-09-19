<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yai8d9m1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yai8d9m1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-hexagon-filled" {...props}></Icon>
