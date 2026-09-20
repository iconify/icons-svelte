<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlb3zlrpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlb3zlrpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:t-shirt-2-line" {...props}></Icon>
