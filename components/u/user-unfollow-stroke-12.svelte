<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz6lpmbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pz6lpmbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-unfollow-stroke-12" {...props}></Icon>
