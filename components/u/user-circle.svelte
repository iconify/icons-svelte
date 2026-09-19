<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwft3nb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwft3nb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-circle" {...props}></Icon>
