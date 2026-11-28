<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcqu69boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcqu69boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sd-card-check" {...props}></Icon>
