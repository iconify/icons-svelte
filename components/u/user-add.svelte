<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbe84dbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbe84dbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:user-add" {...props}></Icon>
