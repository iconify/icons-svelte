<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meh55mbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="meh55mbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:screen-share-off" {...props}></Icon>
