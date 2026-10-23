<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfpjayb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfpjayb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-x" {...props}></Icon>
