<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onhuknpmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onhuknpmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-down-light" {...props}></Icon>
