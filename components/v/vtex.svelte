<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl3-l5bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl3-l5bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vtex" {...props}></Icon>
