<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-taz-bdu.css';
import '../../css/f/fkg5rrbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p-taz-bdu"/><path class="fkg5rrbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunset-48" {...props}></Icon>
