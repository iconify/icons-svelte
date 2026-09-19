<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-6av_bac.css';
import '../../css/g/gw0lhg8wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v-6av_bac"/><path class="gw0lhg8wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:usb" {...props}></Icon>
