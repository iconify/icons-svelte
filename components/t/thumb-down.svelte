<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psmddnbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psmddnbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:thumb-down" {...props}></Icon>
