<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqba5yb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqba5yb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:undb-light" {...props}></Icon>
