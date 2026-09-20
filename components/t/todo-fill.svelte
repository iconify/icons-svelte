<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7zsl-bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7zsl-bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:todo-fill" {...props}></Icon>
