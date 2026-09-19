<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bviy_rbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bviy_rbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-linkedin" {...props}></Icon>
