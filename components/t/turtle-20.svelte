<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly7vjva2u.css';
import '../../css/s/siiy5zxln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ly7vjva2u"/><path class="siiy5zxln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:turtle-20" {...props}></Icon>
