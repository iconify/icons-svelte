<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg_n4mbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_n4mbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-align-justify-end" {...props}></Icon>
