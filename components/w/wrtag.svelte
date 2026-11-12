<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn4_-syio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xn4_-syio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wrtag" {...props}></Icon>
