<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqpg8_bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqpg8_bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yamlresume-dark" {...props}></Icon>
