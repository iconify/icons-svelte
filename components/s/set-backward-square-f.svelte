<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp_1n0ejz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="jp_1n0ejz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:set-backward-square-f" {...props}></Icon>
