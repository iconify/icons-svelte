<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu2zf6bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu2zf6bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:space-ship-fill" {...props}></Icon>
