<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/selaf8bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="selaf8bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:tablet-fill" {...props}></Icon>
