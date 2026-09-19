<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9kskhbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k9kskhbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:traffic-lights-green" {...props}></Icon>
