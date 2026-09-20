<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihbbv98gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihbbv98gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rybbit-dark" {...props}></Icon>
