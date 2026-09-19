<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrob_ccbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nrob_ccbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:six-of-bamboos-mahjong-filled" {...props}></Icon>
