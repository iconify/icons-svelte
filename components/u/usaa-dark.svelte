<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjcdnt86x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjcdnt86x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usaa-dark" {...props}></Icon>
