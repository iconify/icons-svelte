<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alh4-efxe.css';
import '../../css/p/p6thd6bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="alh4-efxe"/><path class="p6thd6bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:share-alt" {...props}></Icon>
