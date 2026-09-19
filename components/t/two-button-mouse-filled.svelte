<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pser2-bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pser2-bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:two-button-mouse-filled" {...props}></Icon>
