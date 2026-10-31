<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqja1p-lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqja1p-lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-letter-h" {...props}></Icon>
