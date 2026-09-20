<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlxaoh3ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlxaoh3ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:soundcloud-logo" {...props}></Icon>
