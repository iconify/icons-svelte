<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a51uagbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a51uagbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:screen-pc-tower-settings" {...props}></Icon>
