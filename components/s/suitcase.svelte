<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdinptbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdinptbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:suitcase" {...props}></Icon>
