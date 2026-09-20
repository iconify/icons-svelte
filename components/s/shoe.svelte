<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as3o3em2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="as3o3em2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:shoe" {...props}></Icon>
