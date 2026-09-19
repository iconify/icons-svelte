<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icn6rqond.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="icn6rqond"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:upload-stroke-16" {...props}></Icon>
