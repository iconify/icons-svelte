<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijemdm6ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ijemdm6ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:watchguard-dark" {...props}></Icon>
