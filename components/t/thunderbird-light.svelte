<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4vr_gbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4vr_gbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thunderbird-light" {...props}></Icon>
