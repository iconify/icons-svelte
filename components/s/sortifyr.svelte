<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_7dyob4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k_7dyob4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sortifyr" {...props}></Icon>
