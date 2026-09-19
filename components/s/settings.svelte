<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4jze1rqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="y4jze1rqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:settings" {...props}></Icon>
