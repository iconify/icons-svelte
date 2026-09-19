<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkbu5vuyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tkbu5vuyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:underline-fill-12" {...props}></Icon>
