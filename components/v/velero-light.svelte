<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bht_f5brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bht_f5brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:velero-light" {...props}></Icon>
