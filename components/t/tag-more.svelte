<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py4q2dbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="py4q2dbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tag-more" {...props}></Icon>
