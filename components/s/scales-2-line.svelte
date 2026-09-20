<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecy_txqvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecy_txqvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scales-2-line" {...props}></Icon>
