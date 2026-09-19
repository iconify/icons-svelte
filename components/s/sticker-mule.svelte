<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvge0qb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="lvge0qb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:sticker-mule" {...props}></Icon>
