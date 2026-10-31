<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtc5v_8lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtc5v_8lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wavy-close-round" {...props}></Icon>
