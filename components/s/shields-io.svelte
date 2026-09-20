<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfwq3cbmt.css';
import '../../css/b/b8_9rtbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfwq3cbmt"/><path class="b8_9rtbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shields-io" {...props}></Icon>
