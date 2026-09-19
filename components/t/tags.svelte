<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7hzi319x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="m7hzi319x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tags" {...props}></Icon>
