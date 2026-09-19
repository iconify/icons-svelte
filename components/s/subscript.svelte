<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krven8k4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="krven8k4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:subscript" {...props}></Icon>
