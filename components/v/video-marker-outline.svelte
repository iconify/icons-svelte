<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5kgi6kpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5kgi6kpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-marker-outline" {...props}></Icon>
