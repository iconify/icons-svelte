<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-4k6nraj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-4k6nraj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-outline" {...props}></Icon>
