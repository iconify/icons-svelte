<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o27827bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o27827bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-arrow-down" {...props}></Icon>
