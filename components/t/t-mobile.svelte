<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv9b7tbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qv9b7tbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:t-mobile" {...props}></Icon>
