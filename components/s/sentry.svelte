<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9i0j_jez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":200};
const content = `<path class="y9i0j_jez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:sentry" {...props}></Icon>
