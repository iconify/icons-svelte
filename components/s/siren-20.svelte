<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn_rhpmlt.css';
import '../../css/i/inx0u8fpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bn_rhpmlt"/><path class="inx0u8fpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:siren-20" {...props}></Icon>
