<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz4769byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qz4769byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:share-fill" {...props}></Icon>
