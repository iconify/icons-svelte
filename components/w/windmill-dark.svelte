<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-0y0ftzh.css';
import '../../css/q/q-dq2zato.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-0y0ftzh"/><path class="q-dq2zato"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windmill-dark" {...props}></Icon>
