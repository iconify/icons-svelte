<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsr7ujquy.css';
import '../../css/b/b42j7_b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rsr7ujquy"/><path class="b42j7_b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shopping-catalog" {...props}></Icon>
