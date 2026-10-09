<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3t12zu5x.css';
import '../../css/i/io22ipbhv.css';
import '../../css/s/s63-krb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3t12zu5x"/><path class="io22ipbhv"/><path class="s63-krb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whale-20" {...props}></Icon>
