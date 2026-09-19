<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0evypbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f0evypbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:traefikmesh-wordmark" {...props}></Icon>
