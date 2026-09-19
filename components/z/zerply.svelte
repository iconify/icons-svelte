<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juqe5accg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="juqe5accg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:zerply" {...props}></Icon>
