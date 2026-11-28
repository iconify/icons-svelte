<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikcs-8xax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikcs-8xax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-0" {...props}></Icon>
