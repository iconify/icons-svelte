<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnp3iub6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bnp3iub6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:table-with-chairs" {...props}></Icon>
