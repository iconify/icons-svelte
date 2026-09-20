<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi251m7kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qi251m7kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yabin-light" {...props}></Icon>
