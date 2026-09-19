<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myuy8im6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="myuy8im6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:wrench" {...props}></Icon>
