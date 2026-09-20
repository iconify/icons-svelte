<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fevqpxbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fevqpxbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toys-outline" {...props}></Icon>
