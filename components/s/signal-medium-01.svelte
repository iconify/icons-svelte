<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g728pbjen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g728pbjen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-medium-01" {...props}></Icon>
