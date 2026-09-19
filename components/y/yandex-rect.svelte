<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4ozfu2_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="w4ozfu2_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:yandex-rect" {...props}></Icon>
