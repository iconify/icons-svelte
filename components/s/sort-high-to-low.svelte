<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hikc9m3jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="hikc9m3jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sort-high-to-low" {...props}></Icon>
