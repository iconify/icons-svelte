<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppbonk68x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbonk68x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:xbox-x" {...props}></Icon>
