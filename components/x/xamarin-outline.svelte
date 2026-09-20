<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi9fd7blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi9fd7blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xamarin-outline" {...props}></Icon>
