<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi974y_9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi974y_9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:saudi-riyal" {...props}></Icon>
