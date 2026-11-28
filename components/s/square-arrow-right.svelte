<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os59_phhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os59_phhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-arrow-right" {...props}></Icon>
