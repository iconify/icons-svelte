<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jol61g51n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jol61g51n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:utility-pole" {...props}></Icon>
