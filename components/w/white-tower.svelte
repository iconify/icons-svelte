<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opn9adbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="opn9adbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:white-tower" {...props}></Icon>
