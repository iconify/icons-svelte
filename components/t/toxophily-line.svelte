<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeo0uab8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oeo0uab8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toxophily-line" {...props}></Icon>
