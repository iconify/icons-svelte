<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8xrzubfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8xrzubfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-octagon-solid" {...props}></Icon>
