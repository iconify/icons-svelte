<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkf05g6mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkf05g6mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-community-fill" {...props}></Icon>
