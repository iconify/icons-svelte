<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvjmzfm2h.css';
import '../../css/a/ay64in9vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lvjmzfm2h"/><path class="ay64in9vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surfshark" {...props}></Icon>
