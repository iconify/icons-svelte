<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkkupx0gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkkupx0gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tangerine-ui-dark" {...props}></Icon>
