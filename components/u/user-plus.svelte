<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9tks-8da.css';
import '../../css/f/flesb1b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9tks-8da"/><path class="flesb1b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:user-plus" {...props}></Icon>
