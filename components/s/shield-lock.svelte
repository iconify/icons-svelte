<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao65_1bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao65_1bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shield-lock" {...props}></Icon>
