<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq8g1iq7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq8g1iq7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smartwatch-check" {...props}></Icon>
