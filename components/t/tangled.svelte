<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p27bqc3bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p27bqc3bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tangled" {...props}></Icon>
