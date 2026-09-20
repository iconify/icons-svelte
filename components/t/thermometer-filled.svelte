<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzz-d2-zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bzz-d2-zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:thermometer-filled" {...props}></Icon>
