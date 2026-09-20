<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l46kd7boi.css';
import '../../css/r/rdwksvbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l46kd7boi"/><path class="rdwksvbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:science-molecule-bold" {...props}></Icon>
