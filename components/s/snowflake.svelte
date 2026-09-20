<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-3upowbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="o-3upowbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:snowflake" {...props}></Icon>
