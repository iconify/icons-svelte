<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbg6tnsmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pbg6tnsmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:tree-unspecified-14" {...props}></Icon>
