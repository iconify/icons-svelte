<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1gj65euc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1gj65euc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-trunk" {...props}></Icon>
