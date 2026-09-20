<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m16-f66mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m16-f66mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:scale-unbalanced" {...props}></Icon>
