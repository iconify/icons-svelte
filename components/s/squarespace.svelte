<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbynunb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qbynunb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:squarespace" {...props}></Icon>
