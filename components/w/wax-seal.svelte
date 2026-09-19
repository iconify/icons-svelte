<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwm54coxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwm54coxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wax-seal" {...props}></Icon>
