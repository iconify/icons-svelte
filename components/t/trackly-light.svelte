<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz-47q_de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xz-47q_de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trackly-light" {...props}></Icon>
