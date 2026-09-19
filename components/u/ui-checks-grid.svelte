<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se058gbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="se058gbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ui-checks-grid" {...props}></Icon>
