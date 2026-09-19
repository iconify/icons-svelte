<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el_-m5xbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="el_-m5xbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:servicestack" {...props}></Icon>
