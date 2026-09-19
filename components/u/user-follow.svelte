<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpmg4f9qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mpmg4f9qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:user-follow" {...props}></Icon>
