<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygh_3sbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ygh_3sbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-outdated-fill-16" {...props}></Icon>
