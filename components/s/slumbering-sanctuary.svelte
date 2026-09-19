<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyxbc2xdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyxbc2xdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slumbering-sanctuary" {...props}></Icon>
