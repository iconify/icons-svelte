<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-715-84a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-715-84a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watering-can" {...props}></Icon>
