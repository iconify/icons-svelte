<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwa86wb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rwa86wb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tower" {...props}></Icon>
