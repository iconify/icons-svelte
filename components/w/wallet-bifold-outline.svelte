<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3cn4kdzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3cn4kdzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wallet-bifold-outline" {...props}></Icon>
