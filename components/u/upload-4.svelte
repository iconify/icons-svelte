<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu14mdo9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yu14mdo9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:upload-4" {...props}></Icon>
