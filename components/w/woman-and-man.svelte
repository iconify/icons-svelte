<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/try1uhstd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="try1uhstd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:woman-and-man" {...props}></Icon>
