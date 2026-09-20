<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnb8f3bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jnb8f3bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wealthfolio-light" {...props}></Icon>
