<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyp808bel.css';
import '../../css/a/ar82p3r0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyp808bel"/><path class="ar82p3r0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spooty-light" {...props}></Icon>
