<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4w5gdb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="o4w5gdb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:stack" {...props}></Icon>
