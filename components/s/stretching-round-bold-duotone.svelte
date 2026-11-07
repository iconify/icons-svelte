<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay5dbdcag.css';
import '../../css/e/emvqbbbmt.css';
import '../../css/k/kg0jzztbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay5dbdcag"/><path clip-rule="evenodd" class="emvqbbbmt"/><path class="kg0jzztbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stretching-round-bold-duotone" {...props}></Icon>
