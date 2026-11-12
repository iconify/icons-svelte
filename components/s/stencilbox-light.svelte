<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/starytbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="starytbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stencilbox-light" {...props}></Icon>
