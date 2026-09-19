<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abyirpbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="abyirpbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:theodolite" {...props}></Icon>
