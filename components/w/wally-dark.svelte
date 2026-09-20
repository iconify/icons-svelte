<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9v99dbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i9v99dbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wally-dark" {...props}></Icon>
