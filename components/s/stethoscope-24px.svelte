<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcjx7jhaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcjx7jhaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stethoscope-24px" {...props}></Icon>
