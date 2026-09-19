<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svvim6bry.css';
import '../../css/x/x8snpsbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="svvim6bry"/><path class="x8snpsbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stacked-move" {...props}></Icon>
