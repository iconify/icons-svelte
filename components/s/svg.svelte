<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uce955b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uce955b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:svg" {...props}></Icon>
