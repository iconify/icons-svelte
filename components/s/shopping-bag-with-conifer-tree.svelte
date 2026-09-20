<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bubm2b0su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bubm2b0su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-conifer-tree" {...props}></Icon>
