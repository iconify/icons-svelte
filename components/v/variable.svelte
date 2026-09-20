<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_c8fjbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_c8fjbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:variable" {...props}></Icon>
