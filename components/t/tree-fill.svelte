<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar9t0wyvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ar9t0wyvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:tree-fill" {...props}></Icon>
