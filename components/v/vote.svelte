<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyq_xjgvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hyq_xjgvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:vote" {...props}></Icon>
