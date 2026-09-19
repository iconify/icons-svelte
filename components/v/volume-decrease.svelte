<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awsw08b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="awsw08b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:volume-decrease" {...props}></Icon>
