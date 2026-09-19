<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6ja8kb8n.css';
import '../../css/v/v1cwuvwqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p6ja8kb8n"/><path class="v1cwuvwqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:subtract-filled" {...props}></Icon>
