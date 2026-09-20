<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p31jd6bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p31jd6bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:save" {...props}></Icon>
