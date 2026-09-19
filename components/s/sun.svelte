<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg8y9i1fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":472};
const content = `<path class="jg8y9i1fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:sun" {...props}></Icon>
