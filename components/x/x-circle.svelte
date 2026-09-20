<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grp5ld88p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grp5ld88p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-circle" {...props}></Icon>
