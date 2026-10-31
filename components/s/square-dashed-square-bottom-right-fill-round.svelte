<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm9o7dbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm9o7dbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-square-bottom-right-fill-round" {...props}></Icon>
