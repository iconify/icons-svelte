<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s027-x4sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s027-x4sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:stripe" {...props}></Icon>
