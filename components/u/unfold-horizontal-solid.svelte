<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvkz2fbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvkz2fbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:unfold-horizontal-solid" {...props}></Icon>
