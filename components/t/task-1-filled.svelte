<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_hxwwbci.css';
import '../../css/c/c74g0s1af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="c74g0s1af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-1-filled" {...props}></Icon>
