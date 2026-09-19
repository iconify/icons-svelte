<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rokj9f_9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rokj9f_9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-plus" {...props}></Icon>
