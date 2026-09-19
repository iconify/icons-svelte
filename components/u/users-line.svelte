<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m23cf6bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m23cf6bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:users-line" {...props}></Icon>
