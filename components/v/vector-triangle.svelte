<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaq560y5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jaq560y5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-triangle" {...props}></Icon>
