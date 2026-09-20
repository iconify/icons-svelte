<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz5b27bcw.css';
import '../../css/g/g205xvbso.css';
import '../../css/m/mqgqm8b7z.css';
import '../../css/n/ncstxp-xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2400,"height":2800};
const content = `<path class="rz5b27bcw"/><g class="g205xvbso"><path class="mqgqm8b7z"/><path class="ncstxp-xu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:twitch" {...props}></Icon>
