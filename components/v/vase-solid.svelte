<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvaosqbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvaosqbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vase-solid" {...props}></Icon>
