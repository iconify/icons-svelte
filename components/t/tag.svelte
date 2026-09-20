<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn655r21a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dn655r21a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tag" {...props}></Icon>
