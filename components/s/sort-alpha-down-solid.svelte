<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-b90kbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o-b90kbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-alpha-down-solid" {...props}></Icon>
