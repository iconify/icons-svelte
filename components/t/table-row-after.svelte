<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7gp0_b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7gp0_b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:table-row-after" {...props}></Icon>
