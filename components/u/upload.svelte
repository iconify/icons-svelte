<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbrixeswg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbrixeswg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:upload" {...props}></Icon>
