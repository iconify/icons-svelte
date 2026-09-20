<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv9k1mbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rv9k1mbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:top-outline" {...props}></Icon>
