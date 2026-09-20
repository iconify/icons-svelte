<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixrj4gb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixrj4gb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-speaker-minimalistic-bold" {...props}></Icon>
