<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixf3ftt8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixf3ftt8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:sad" {...props}></Icon>
