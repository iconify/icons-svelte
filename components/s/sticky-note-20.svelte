<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fve4swbro.css';
import '../../css/o/os335z1oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fve4swbro"/><path class="os335z1oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticky-note-20" {...props}></Icon>
