<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmz8bn8eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmz8bn8eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:thermometer" {...props}></Icon>
