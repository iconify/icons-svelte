<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjg0ixb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cjg0ixb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:zrx" {...props}></Icon>
