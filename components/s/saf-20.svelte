<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyzll6bdo.css';
import '../../css/z/z6uphtb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oyzll6bdo"/><path class="z6uphtb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saf-20" {...props}></Icon>
