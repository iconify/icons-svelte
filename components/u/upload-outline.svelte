<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wszt9mr6r.css';
import '../../css/z/zurn3powf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wszt9mr6r"/><path class="zurn3powf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:upload-outline" {...props}></Icon>
