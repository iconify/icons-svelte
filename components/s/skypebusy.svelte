<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfxlr7j4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jfxlr7j4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:skypebusy" {...props}></Icon>
