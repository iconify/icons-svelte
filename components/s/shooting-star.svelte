<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwcr48b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwcr48b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shooting-star" {...props}></Icon>
