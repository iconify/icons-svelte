<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjkqadw8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjkqadw8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:solar-angle-outline" {...props}></Icon>
