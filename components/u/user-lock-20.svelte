<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9-5dabgd.css';
import '../../css/x/x-j00pe6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p9-5dabgd"/><path class="x-j00pe6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-lock-20" {...props}></Icon>
