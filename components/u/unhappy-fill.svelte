<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j71x9tmmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j71x9tmmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unhappy-fill" {...props}></Icon>
