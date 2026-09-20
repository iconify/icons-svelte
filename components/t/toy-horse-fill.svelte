<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r560ybvhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r560ybvhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toy-horse-fill" {...props}></Icon>
