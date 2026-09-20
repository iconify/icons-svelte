<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufdfntbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ufdfntbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:washing-machine" {...props}></Icon>
