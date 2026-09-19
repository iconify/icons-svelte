<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awks9rbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="awks9rbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:share" {...props}></Icon>
