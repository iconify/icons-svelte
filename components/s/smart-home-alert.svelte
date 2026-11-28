<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-9m29bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-9m29bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smart-home-alert" {...props}></Icon>
