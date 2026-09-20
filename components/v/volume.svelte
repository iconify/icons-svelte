<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojwgjs_ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojwgjs_ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:volume" {...props}></Icon>
