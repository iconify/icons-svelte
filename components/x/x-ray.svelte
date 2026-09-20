<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfc0jvbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfc0jvbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:x-ray" {...props}></Icon>
