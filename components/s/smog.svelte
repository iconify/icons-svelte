<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo3gpe9bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zo3gpe9bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:smog" {...props}></Icon>
