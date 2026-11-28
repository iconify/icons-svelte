<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf7jnuxhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf7jnuxhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sushi" {...props}></Icon>
