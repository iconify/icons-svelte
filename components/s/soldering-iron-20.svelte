<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twyecdg0k.css';
import '../../css/t/tzg0a7gil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="twyecdg0k"/><path class="tzg0a7gil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soldering-iron-20" {...props}></Icon>
