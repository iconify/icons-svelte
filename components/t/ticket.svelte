<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r67kl8-5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r67kl8-5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ticket" {...props}></Icon>
