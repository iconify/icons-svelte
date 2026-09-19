<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmh10nt-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="zmh10nt-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:yandex" {...props}></Icon>
