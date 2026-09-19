<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chffm619i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="chffm619i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:trailer" {...props}></Icon>
