<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-yctv5li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a-yctv5li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-minus-solid" {...props}></Icon>
