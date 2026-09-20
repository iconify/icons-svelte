<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve-xeub_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve-xeub_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tablet" {...props}></Icon>
