<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nky2nab7l.css';
import '../../css/t/t0669_bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nky2nab7l"/><path class="t0669_bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wrench-screwdriver-16-solid" {...props}></Icon>
