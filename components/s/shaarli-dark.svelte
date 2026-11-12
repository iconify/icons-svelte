<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4q6qbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wt4q6qbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shaarli-dark" {...props}></Icon>
