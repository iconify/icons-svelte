<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnalu2bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnalu2bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:virus-off" {...props}></Icon>
