<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp_r4gbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rp_r4gbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-filled" {...props}></Icon>
