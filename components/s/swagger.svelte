<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooxg0mb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooxg0mb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:swagger" {...props}></Icon>
