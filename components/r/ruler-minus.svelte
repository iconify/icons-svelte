<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auubz8njb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auubz8njb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ruler-minus" {...props}></Icon>
