<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l50o5rb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l50o5rb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sleepy2" {...props}></Icon>
