<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olyod0b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olyod0b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:underline-solid" {...props}></Icon>
