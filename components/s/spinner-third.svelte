<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4-1glbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4-1glbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:spinner-third" {...props}></Icon>
