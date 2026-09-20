<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctezs365s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctezs365s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidarr-dark" {...props}></Icon>
