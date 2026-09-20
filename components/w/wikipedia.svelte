<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz0800s7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz0800s7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wikipedia" {...props}></Icon>
