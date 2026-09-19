<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfebhubri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jfebhubri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:wifi" {...props}></Icon>
