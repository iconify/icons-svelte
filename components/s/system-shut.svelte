<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imrr2wcsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imrr2wcsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:system-shut" {...props}></Icon>
