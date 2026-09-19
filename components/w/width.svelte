<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzatv2dyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzatv2dyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:width" {...props}></Icon>
