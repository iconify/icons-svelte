<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiwa63bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiwa63bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-monitor-bold" {...props}></Icon>
