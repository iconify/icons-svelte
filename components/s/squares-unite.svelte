<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdat2y5gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdat2y5gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:squares-unite" {...props}></Icon>
