<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl6y03tsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yl6y03tsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:tumblr-square" {...props}></Icon>
