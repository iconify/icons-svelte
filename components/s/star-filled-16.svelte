<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg588xblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gg588xblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:star-filled-16" {...props}></Icon>
