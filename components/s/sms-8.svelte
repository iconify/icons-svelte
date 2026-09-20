<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxbx25zyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxbx25zyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-8" {...props}></Icon>
