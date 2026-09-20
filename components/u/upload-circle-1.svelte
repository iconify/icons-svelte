<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s12b9m4yl.css';
import '../../css/c/c-rl6lbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="s12b9m4yl"/><path clip-rule="evenodd" class="c-rl6lbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:upload-circle-1" {...props}></Icon>
