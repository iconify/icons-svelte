<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxlcdsb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxlcdsb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tp-link" {...props}></Icon>
