<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7xgi5bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f7xgi5bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:temperature" {...props}></Icon>
