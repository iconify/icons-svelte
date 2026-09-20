<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lksscjg4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lksscjg4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rusta-light" {...props}></Icon>
