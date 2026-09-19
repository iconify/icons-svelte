<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s26a_tbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s26a_tbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sun-radiations" {...props}></Icon>
