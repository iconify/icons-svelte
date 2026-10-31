<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp8z4moyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp8z4moyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shower-round" {...props}></Icon>
