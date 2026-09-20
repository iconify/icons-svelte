<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt32cgb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt32cgb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:upload-line" {...props}></Icon>
