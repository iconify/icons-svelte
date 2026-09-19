<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8z775b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8z775b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:smartphone-nfc" {...props}></Icon>
