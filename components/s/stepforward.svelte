<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpb6u2b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="dpb6u2b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:stepforward" {...props}></Icon>
