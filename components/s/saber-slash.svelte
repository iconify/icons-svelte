<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxt5wfc_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxt5wfc_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:saber-slash" {...props}></Icon>
