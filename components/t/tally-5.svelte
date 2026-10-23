<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuogiubpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuogiubpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tally-5" {...props}></Icon>
