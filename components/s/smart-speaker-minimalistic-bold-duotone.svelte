<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwczj0bva.css';
import '../../css/i/ieaqgcb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwczj0bva"/><path class="ieaqgcb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-speaker-minimalistic-bold-duotone" {...props}></Icon>
