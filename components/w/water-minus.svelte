<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce6ad26an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce6ad26an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-minus" {...props}></Icon>
