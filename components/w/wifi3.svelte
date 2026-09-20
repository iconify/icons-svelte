<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcyefbb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcyefbb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wifi3" {...props}></Icon>
