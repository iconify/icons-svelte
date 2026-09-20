<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4fod_bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t4fod_bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:xbox" {...props}></Icon>
