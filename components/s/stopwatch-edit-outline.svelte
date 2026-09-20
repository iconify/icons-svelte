<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-7r6lf6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-7r6lf6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-edit-outline" {...props}></Icon>
