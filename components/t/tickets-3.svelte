<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ro5bbhu.css';
import '../../css/c/ck3x9ggdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ro5bbhu"/><path clip-rule="evenodd" class="ck3x9ggdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tickets-3" {...props}></Icon>
