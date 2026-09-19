<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfxt7ubbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfxt7ubbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:signal-cellular-0" {...props}></Icon>
