<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qugdhub4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qugdhub4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:window" {...props}></Icon>
