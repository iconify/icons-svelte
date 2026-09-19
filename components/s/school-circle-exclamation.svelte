<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9bqularh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="n9bqularh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:school-circle-exclamation" {...props}></Icon>
