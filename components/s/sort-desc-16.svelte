<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb24mfbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pb24mfbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sort-desc-16" {...props}></Icon>
