<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-m8bqbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-m8bqbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:truenas-scale-light" {...props}></Icon>
