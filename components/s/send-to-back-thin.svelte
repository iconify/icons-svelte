<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7a05abhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g7a05abhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-to-back-thin" {...props}></Icon>
