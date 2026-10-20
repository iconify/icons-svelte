<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0yys_sjp.css';
import '../../css/p/pkv646nkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z0yys_sjp"/><path class="pkv646nkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-vibrate-48" {...props}></Icon>
