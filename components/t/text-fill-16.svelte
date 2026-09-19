<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbb8rq6gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tbb8rq6gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-fill-16" {...props}></Icon>
