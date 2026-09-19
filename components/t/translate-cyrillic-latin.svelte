<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj1ehrbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hj1ehrbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-cyrillic-latin" {...props}></Icon>
