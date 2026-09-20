<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktrc50b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktrc50b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:virus-outline" {...props}></Icon>
