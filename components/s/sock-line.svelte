<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j48fsi5yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j48fsi5yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sock-line" {...props}></Icon>
