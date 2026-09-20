<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx3490c6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mx3490c6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:vpn-shield-bold" {...props}></Icon>
