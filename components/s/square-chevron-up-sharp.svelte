<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ovz_bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ovz_bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-chevron-up-sharp" {...props}></Icon>
