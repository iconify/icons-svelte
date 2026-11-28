<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv75_pb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv75_pb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:stop" {...props}></Icon>
