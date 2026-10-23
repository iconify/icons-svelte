<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yalxtnbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yalxtnbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:train-track" {...props}></Icon>
