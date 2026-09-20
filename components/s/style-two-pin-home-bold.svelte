<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuxo34wrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuxo34wrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:style-two-pin-home-bold" {...props}></Icon>
