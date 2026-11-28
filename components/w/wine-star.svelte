<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsz5y4byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsz5y4byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wine-star" {...props}></Icon>
