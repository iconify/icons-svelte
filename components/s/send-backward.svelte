<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ht_0i4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="s3ht_0i4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-backward" {...props}></Icon>
