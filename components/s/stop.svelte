<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz1of_bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qz1of_bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:stop" {...props}></Icon>
