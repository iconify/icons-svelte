<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acf1ytbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="acf1ytbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skip-back-20" {...props}></Icon>
