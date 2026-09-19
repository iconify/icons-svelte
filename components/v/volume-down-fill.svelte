<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/necg2lb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="necg2lb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:volume-down-fill" {...props}></Icon>
