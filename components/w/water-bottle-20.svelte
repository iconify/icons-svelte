<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkm6ueyhw.css';
import '../../css/r/rdt8hgb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tkm6ueyhw"/><path class="rdt8hgb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-bottle-20" {...props}></Icon>
