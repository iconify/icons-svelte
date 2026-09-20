<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g16ka0d3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g16ka0d3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tangerine-ui-light" {...props}></Icon>
