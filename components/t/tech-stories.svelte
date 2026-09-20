<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3rebkngr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3rebkngr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:tech-stories" {...props}></Icon>
