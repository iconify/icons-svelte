<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9mgdhkad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g9mgdhkad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:table-row-after" {...props}></Icon>
