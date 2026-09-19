<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxgthgt6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uxgthgt6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker" {...props}></Icon>
