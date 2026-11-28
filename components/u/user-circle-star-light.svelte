<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxly0_vhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qxly0_vhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-circle-star-light" {...props}></Icon>
