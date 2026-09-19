<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx5hxgbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zx5hxgbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:signpost-2-fill" {...props}></Icon>
