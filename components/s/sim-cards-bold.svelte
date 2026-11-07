<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxkkglg1b.css';
import '../../css/n/n32zpyb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxkkglg1b"/><path clip-rule="evenodd" class="n32zpyb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sim-cards-bold" {...props}></Icon>
