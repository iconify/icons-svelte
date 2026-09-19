<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/triztubxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="triztubxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:session-in-progress" {...props}></Icon>
