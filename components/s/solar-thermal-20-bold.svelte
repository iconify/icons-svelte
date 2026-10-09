<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b52to0bjp.css';
import '../../css/p/pfj9i6b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b52to0bjp"/><path class="pfj9i6b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-thermal-20-bold" {...props}></Icon>
