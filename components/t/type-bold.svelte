<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hekdg5bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hekdg5bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:type-bold" {...props}></Icon>
