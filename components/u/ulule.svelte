<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr6401bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr6401bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ulule" {...props}></Icon>
