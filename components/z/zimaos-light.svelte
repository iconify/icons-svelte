<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gar-mkovf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gar-mkovf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zimaos-light" {...props}></Icon>
