<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6cp4xa2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q6cp4xa2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:stop2" {...props}></Icon>
