<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evpgkejzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evpgkejzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:strikethrough-duotone" {...props}></Icon>
