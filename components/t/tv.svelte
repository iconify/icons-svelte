<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpb0q2cet.css';
import '../../css/l/l8k158baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hpb0q2cet"/><path class="l8k158baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tv" {...props}></Icon>
