<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umk9o8bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="umk9o8bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:textformat-superscript" {...props}></Icon>
