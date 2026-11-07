<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0sxd4ipq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d0sxd4ipq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-navigation-outline" {...props}></Icon>
