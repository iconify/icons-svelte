<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4-qo_bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r4-qo_bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wigwam-dark" {...props}></Icon>
