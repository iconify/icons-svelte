<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-keie.css';
import '../../css/w/w3lddg.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-76.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-keie"/><path class="w3lddg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:thumbs-up-twotone" {...props}></Icon>
