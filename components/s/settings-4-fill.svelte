<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeqj8mb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeqj8mb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-4-fill" {...props}></Icon>
