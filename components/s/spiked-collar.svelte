<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa_radcde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wa_radcde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-collar" {...props}></Icon>
