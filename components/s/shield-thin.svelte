<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljl08gbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljl08gbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shield-thin" {...props}></Icon>
