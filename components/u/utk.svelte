<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqwedw9qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iqwedw9qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:utk" {...props}></Icon>
