<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udhv20bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1025};
const content = `<path class="udhv20bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:simalt" {...props}></Icon>
