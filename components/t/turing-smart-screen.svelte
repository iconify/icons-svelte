<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6ckg4bnd.css';
import '../../css/d/dysu5hdsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6ckg4bnd"/><path class="dysu5hdsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:turing-smart-screen" {...props}></Icon>
