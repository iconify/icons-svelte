<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldjcn78ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ldjcn78ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:volume-low" {...props}></Icon>
