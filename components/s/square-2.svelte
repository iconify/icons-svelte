<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj3h-ftar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj3h-ftar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-2" {...props}></Icon>
