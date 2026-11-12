<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7hzx7ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7hzx7ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wavelog" {...props}></Icon>
