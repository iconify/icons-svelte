<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axj_glcrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axj_glcrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:star" {...props}></Icon>
