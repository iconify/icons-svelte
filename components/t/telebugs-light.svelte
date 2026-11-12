<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9kzex68f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9kzex68f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:telebugs-light" {...props}></Icon>
