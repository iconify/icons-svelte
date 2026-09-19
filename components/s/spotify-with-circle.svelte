<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be88_obth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="be88_obth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:spotify-with-circle" {...props}></Icon>
