<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cymrcsbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cymrcsbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sort-ascending" {...props}></Icon>
