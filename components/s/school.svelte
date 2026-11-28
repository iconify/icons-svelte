<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4ajrbc5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4ajrbc5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:school" {...props}></Icon>
