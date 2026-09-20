<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz6ow9y5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fz6ow9y5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-email-expressive" {...props}></Icon>
