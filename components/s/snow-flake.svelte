<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuuvg9cpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuuvg9cpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:snow-flake" {...props}></Icon>
