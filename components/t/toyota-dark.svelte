<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz6fvbc1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jz6fvbc1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toyota-dark" {...props}></Icon>
