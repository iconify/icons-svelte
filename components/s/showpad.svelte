<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foa44bdgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="foa44bdgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:showpad" {...props}></Icon>
