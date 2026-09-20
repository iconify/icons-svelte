<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvw8omzpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvw8omzpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:venus" {...props}></Icon>
