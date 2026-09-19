<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_f06ccrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_f06ccrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-fence" {...props}></Icon>
