<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn4gi9b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jn4gi9b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:z-wave-js-ui" {...props}></Icon>
