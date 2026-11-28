<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba7zxubcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba7zxubcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smartphone-check" {...props}></Icon>
