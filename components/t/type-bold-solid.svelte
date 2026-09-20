<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2h-p6key.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2h-p6key"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:type-bold-solid" {...props}></Icon>
