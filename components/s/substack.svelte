<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul21tbbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ul21tbbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:substack" {...props}></Icon>
