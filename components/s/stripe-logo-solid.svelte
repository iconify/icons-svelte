<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikdhr5-2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikdhr5-2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stripe-logo-solid" {...props}></Icon>
