<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm0c7-bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cm0c7-bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:yarn" {...props}></Icon>
