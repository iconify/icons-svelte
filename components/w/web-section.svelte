<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcohcvn_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcohcvn_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:web-section" {...props}></Icon>
