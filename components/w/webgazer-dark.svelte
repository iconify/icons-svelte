<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1dd95b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o1dd95b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webgazer-dark" {...props}></Icon>
