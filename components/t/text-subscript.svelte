<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hthj1nnsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hthj1nnsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-subscript" {...props}></Icon>
