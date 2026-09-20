<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqo2dvk4m.css';
import '../../css/p/p1l0ufzst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqo2dvk4m"/><path class="p1l0ufzst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taj-mahal-line" {...props}></Icon>
