<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjdjl4z7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="zjdjl4z7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stop-circle" {...props}></Icon>
