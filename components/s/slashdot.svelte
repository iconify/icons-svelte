<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3w-4db8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z3w-4db8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:slashdot" {...props}></Icon>
