<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrf2rnkcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrf2rnkcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-f8-filled" {...props}></Icon>
