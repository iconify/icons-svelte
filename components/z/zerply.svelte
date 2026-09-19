<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypohyzbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="ypohyzbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zerply" {...props}></Icon>
