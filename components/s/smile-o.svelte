<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2sfl7j_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="c2sfl7j_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:smile-o" {...props}></Icon>
