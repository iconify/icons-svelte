<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct192wbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct192wbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wear-gas-mask" {...props}></Icon>
