<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hugd8dbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hugd8dbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tooth-solid" {...props}></Icon>
