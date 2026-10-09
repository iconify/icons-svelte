<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdq198b0v.css';
import '../../css/v/vltasnbml.css';
import '../../css/u/u9s6q-bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gdq198b0v"/><path class="vltasnbml"/><path class="u9s6q-bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-kit-48-bold" {...props}></Icon>
