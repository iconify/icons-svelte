<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugqf-vbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugqf-vbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:save-outline" {...props}></Icon>
