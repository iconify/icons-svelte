<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvh1t7b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvh1t7b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vector-triangle-off" {...props}></Icon>
