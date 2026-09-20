<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8pwkeb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8pwkeb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:television-check-fill" {...props}></Icon>
