<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7_ujacyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f7_ujacyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-polo" {...props}></Icon>
