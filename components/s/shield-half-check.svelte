<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi51t6b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi51t6b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shield-half-check" {...props}></Icon>
