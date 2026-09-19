<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feplapb-m.css';
import '../../css/a/afrri1boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feplapb-m"/><path class="afrri1boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:select-none" {...props}></Icon>
