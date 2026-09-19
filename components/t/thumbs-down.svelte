<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2_v63kit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2_v63kit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:thumbs-down" {...props}></Icon>
