<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bafgg-byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bafgg-byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-box" {...props}></Icon>
