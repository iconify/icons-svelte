<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njks3in5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="njks3in5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-fill" {...props}></Icon>
