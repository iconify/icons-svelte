<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-s39uks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-s39uks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sword-attack" {...props}></Icon>
