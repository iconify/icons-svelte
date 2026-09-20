<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7k3eshrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7k3eshrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sound-module-line" {...props}></Icon>
