<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f69z4_btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f69z4_btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-number-8-filled" {...props}></Icon>
