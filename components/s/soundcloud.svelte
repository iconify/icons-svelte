<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptr56cnqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptr56cnqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:soundcloud" {...props}></Icon>
