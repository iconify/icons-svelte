<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snw4uebvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="snw4uebvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:switch-horizontal" {...props}></Icon>
