<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv2opow9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iv2opow9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-low-solid" {...props}></Icon>
