<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvv0o5bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lvv0o5bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamlink-light" {...props}></Icon>
