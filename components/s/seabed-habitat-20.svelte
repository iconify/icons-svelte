<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ni6vb5b.css';
import '../../css/i/i75_mcddu.css';
import '../../css/g/gqyz_obje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g0ni6vb5b"/><path class="i75_mcddu"/><path class="gqyz_obje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seabed-habitat-20" {...props}></Icon>
