<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzl7qhbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzl7qhbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:unfold-less" {...props}></Icon>
