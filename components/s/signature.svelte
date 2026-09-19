<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pedwd1-dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pedwd1-dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:signature" {...props}></Icon>
