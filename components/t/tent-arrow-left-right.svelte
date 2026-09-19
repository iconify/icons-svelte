<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwrwo52mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gwrwo52mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tent-arrow-left-right" {...props}></Icon>
