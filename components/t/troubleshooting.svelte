<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ror7eiqam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ror7eiqam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:troubleshooting" {...props}></Icon>
