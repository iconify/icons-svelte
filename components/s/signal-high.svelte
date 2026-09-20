<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qah5gg87y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qah5gg87y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:signal-high" {...props}></Icon>
