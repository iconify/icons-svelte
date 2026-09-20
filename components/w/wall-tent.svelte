<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpz043b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zpz043b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wall-tent" {...props}></Icon>
