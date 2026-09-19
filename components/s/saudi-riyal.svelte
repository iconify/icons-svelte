<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er3yn_rep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er3yn_rep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:saudi-riyal" {...props}></Icon>
