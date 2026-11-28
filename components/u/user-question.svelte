<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1kcf2va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1kcf2va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-question" {...props}></Icon>
