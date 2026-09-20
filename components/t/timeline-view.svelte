<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5vyqz5pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5vyqz5pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:timeline-view" {...props}></Icon>
