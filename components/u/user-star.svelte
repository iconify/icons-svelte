<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gplu-xtlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gplu-xtlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-star" {...props}></Icon>
