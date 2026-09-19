<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqxm_jb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="rqxm_jb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-bag" {...props}></Icon>
