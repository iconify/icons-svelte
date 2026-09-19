<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqbkf44xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kqbkf44xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rupee-sign" {...props}></Icon>
