<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apfifgb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":1024};
const content = `<path class="apfifgb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:usb" {...props}></Icon>
