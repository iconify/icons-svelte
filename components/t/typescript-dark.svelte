<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfmz5lbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfmz5lbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typescript-dark" {...props}></Icon>
