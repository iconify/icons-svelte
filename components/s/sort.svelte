<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zskg0iypq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zskg0iypq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sort" {...props}></Icon>
