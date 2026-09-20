<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruzq9dyfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ruzq9dyfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:x-light" {...props}></Icon>
