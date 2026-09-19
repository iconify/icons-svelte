<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk6mjkb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pk6mjkb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shield-off-filled" {...props}></Icon>
