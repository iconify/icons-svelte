<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txyc7sgll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="txyc7sgll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tandoor-recipes-dark" {...props}></Icon>
