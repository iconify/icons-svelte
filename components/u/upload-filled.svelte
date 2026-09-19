<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pla5l_p9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pla5l_p9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:upload-filled" {...props}></Icon>
