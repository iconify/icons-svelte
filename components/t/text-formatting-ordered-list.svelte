<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2qncv8ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o2qncv8ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-ordered-list" {...props}></Icon>
