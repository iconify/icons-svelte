<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3buq2dzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s3buq2dzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:square-virus" {...props}></Icon>
