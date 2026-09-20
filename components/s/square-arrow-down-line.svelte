<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-u00kfcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-u00kfcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-down-line" {...props}></Icon>
