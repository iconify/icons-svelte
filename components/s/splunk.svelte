<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oovhg-9to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oovhg-9to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:splunk" {...props}></Icon>
