<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf2ekcckn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yf2ekcckn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:snowflake" {...props}></Icon>
