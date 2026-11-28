<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf715lbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf715lbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:server-alert" {...props}></Icon>
