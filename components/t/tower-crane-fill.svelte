<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec6h5ubjk.css';
import '../../css/c/cyglm8gxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec6h5ubjk"/><path class="cyglm8gxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-crane-fill" {...props}></Icon>
