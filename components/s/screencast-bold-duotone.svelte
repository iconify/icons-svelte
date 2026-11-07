<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nphcgbcmt.css';
import '../../css/y/ynsaqab9c.css';
import '../../css/u/uqaz4lb5b.css';
import '../../css/k/ktepy320u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nphcgbcmt"/><path class="ynsaqab9c"/><path class="uqaz4lb5b"/><path class="ktepy320u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screencast-bold-duotone" {...props}></Icon>
