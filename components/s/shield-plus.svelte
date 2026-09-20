<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqfaw-b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqfaw-b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shield-plus" {...props}></Icon>
