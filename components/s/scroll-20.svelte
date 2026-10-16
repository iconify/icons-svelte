<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghip4ybrb.css';
import '../../css/w/wjctu7hsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ghip4ybrb"/><path class="wjctu7hsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scroll-20" {...props}></Icon>
