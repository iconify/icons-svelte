<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpf1hvb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qpf1hvb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sandwich" {...props}></Icon>
