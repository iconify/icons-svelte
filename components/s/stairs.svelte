<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8fqnnf_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="z8fqnnf_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:stairs" {...props}></Icon>
