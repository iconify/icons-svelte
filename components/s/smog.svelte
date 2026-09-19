<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1xy50bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g1xy50bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:smog" {...props}></Icon>
