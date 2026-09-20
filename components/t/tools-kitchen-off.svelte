<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7xeb6bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7xeb6bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tools-kitchen-off" {...props}></Icon>
