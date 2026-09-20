<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-uab2czj.css';
import '../../css/p/pphyynu_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-uab2czj"/><path class="pphyynu_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:truck-2-bold" {...props}></Icon>
