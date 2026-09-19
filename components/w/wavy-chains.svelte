<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqic_w44i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqic_w44i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wavy-chains" {...props}></Icon>
