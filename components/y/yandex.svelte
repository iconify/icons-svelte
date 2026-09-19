<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_r8-tbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="x_r8-tbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yandex" {...props}></Icon>
