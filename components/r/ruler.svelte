<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-2nhuhvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-2nhuhvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ruler" {...props}></Icon>
