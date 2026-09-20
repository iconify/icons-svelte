<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhswl84tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bhswl84tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sunwet-light" {...props}></Icon>
