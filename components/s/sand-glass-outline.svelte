<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpyic3bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wpyic3bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sand-glass-outline" {...props}></Icon>
