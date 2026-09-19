<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te__9_nlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te__9_nlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:snow-flake" {...props}></Icon>
