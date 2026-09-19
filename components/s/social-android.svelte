<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxy1yxb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yxy1yxb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-android" {...props}></Icon>
