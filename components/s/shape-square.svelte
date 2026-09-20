<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psybx4g9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psybx4g9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:shape-square" {...props}></Icon>
