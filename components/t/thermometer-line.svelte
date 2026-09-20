<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jktt-zflc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jktt-zflc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:thermometer-line" {...props}></Icon>
