<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-xlhab4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g-xlhab4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-medium" {...props}></Icon>
