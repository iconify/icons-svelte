<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyt55ki0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyt55ki0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sanitizer-alt" {...props}></Icon>
