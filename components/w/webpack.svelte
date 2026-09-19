<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3f_nlpyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":462,"height":512};
const content = `<path class="f3f_nlpyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:webpack" {...props}></Icon>
