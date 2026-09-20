<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv-tmybja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yv-tmybja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sliders-vertical-16" {...props}></Icon>
