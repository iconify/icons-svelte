<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeq2uhbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zeq2uhbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-favorites" {...props}></Icon>
