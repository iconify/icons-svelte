<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve4n1njjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ve4n1njjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:shield-alt" {...props}></Icon>
