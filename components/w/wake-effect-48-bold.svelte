<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp0dme4mw.css';
import '../../css/r/r1718n6ef.css';
import '../../css/z/z2svp9beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hp0dme4mw"/><path class="r1718n6ef"/><path class="z2svp9beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wake-effect-48-bold" {...props}></Icon>
