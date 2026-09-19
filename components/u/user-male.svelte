<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt7bghb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lt7bghb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:user-male" {...props}></Icon>
