<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0wi9crkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0wi9crkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-05-the-hierophant" {...props}></Icon>
