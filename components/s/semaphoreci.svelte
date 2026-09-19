<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2zrd1-ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g2zrd1-ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:semaphoreci" {...props}></Icon>
