<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrrn-2bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrrn-2bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:signal-low" {...props}></Icon>
