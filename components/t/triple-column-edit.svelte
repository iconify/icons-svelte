<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha5spmbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ha5spmbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:triple-column-edit" {...props}></Icon>
