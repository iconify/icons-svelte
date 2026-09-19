<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgg4whj9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zgg4whj9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shapes-fill-12" {...props}></Icon>
