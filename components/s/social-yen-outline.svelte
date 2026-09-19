<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb6ttobwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pb6ttobwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-yen-outline" {...props}></Icon>
