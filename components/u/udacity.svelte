<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdp0fsn3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qdp0fsn3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:udacity" {...props}></Icon>
