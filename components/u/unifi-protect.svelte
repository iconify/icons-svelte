<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgd3znb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgd3znb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:unifi-protect" {...props}></Icon>
