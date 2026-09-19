<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j31cb_byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j31cb_byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:snow" {...props}></Icon>
