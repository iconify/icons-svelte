<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrw8l6u1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw8l6u1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:xbox-live-logo" {...props}></Icon>
