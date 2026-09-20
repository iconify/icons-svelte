<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufs1ieqpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufs1ieqpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:shanghaimetro" {...props}></Icon>
