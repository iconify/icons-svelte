<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbjntgbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wbjntgbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thunderbird-dark" {...props}></Icon>
