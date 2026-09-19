<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9bibabvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="m9bibabvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:w-upper-case" {...props}></Icon>
