<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je28i7o7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je28i7o7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick" {...props}></Icon>
