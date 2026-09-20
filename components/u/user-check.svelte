<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjk-647jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjk-647jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-check" {...props}></Icon>
