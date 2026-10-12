<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zknk9gucc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zknk9gucc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:thumbs-down-stroke-20" {...props}></Icon>
