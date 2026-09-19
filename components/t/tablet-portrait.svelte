<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twpo036bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="twpo036bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:tablet-portrait" {...props}></Icon>
