<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf2xa4bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf2xa4bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:seatgeek" {...props}></Icon>
