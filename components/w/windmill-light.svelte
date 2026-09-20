<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra4xehcyp.css';
import '../../css/z/zj7rmmb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ra4xehcyp"/><path class="zj7rmmb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windmill-light" {...props}></Icon>
