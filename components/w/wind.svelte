<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fv8dtdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j7fv8dtdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:wind" {...props}></Icon>
