<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhm5ifbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="nhm5ifbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tile-caution-thin" {...props}></Icon>
