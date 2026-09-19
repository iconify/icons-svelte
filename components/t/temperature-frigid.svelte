<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omt7_bbav.css';
import '../../css/y/ymie1nvqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="omt7_bbav"/><path class="ymie1nvqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature-frigid" {...props}></Icon>
