<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo5l4obau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vo5l4obau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:swift-16" {...props}></Icon>
