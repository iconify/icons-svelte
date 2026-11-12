<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szaw_2tpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="szaw_2tpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wrtag-dark" {...props}></Icon>
