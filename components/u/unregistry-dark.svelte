<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me2zngofg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="me2zngofg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unregistry-dark" {...props}></Icon>
