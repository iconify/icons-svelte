<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pde1fbz0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pde1fbz0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-filled" {...props}></Icon>
