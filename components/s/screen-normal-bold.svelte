<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg16o2bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg16o2bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:screen-normal-bold" {...props}></Icon>
