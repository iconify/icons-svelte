<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2w-uwbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2w-uwbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:star-outline" {...props}></Icon>
