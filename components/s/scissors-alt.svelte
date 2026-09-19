<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ve_51rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="y7ve_51rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:scissors-alt" {...props}></Icon>
