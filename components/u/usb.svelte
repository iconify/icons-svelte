<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl6d0daue.css';
import '../../css/h/hnlide_cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gl6d0daue"/><path class="hnlide_cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:usb" {...props}></Icon>
