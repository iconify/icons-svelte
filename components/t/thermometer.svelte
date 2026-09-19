<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frd3b7bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="frd3b7bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:thermometer" {...props}></Icon>
