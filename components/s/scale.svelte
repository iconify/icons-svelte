<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6-09cago.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6-09cago"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:scale" {...props}></Icon>
