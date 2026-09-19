<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw7z-bckb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="bw7z-bckb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:youku" {...props}></Icon>
