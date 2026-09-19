<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myewfdclo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="myewfdclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tachometer-alt" {...props}></Icon>
