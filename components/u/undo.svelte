<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrmfs0crz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrmfs0crz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:undo" {...props}></Icon>
