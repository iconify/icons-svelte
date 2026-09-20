<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh157dkwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gh157dkwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:victoriametrics-light" {...props}></Icon>
