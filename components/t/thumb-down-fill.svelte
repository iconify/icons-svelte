<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9a5ey1ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9a5ey1ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thumb-down-fill" {...props}></Icon>
