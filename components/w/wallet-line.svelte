<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6725hmas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6725hmas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-line" {...props}></Icon>
