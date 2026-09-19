<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iri646bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iri646bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:split-body" {...props}></Icon>
