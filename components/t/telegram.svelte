<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpcxctqsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cpcxctqsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:telegram" {...props}></Icon>
