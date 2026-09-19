<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r02q42ccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r02q42ccy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon-info" {...props}></Icon>
