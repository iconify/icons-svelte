<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd1w9bcas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qd1w9bcas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wizard-staff" {...props}></Icon>
