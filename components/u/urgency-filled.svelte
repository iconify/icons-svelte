<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7t-cc1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dy7t-cc1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:urgency-filled" {...props}></Icon>
