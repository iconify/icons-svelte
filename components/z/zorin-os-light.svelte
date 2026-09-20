<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsba6-s3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dsba6-s3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zorin-os-light" {...props}></Icon>
