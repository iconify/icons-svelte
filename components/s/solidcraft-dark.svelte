<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evge9_brb.css';
import '../../css/j/jdicwcndp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evge9_brb"/><path class="jdicwcndp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:solidcraft-dark" {...props}></Icon>
