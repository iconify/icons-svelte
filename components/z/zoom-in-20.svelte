<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsx9bkbtz.css';
import '../../css/g/gq2n7-bry.css';
import '../../css/m/munnn-b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jsx9bkbtz"/><path class="gq2n7-bry"/><path class="munnn-b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zoom-in-20" {...props}></Icon>
