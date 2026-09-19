<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6efcc-6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6efcc-6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:triangle" {...props}></Icon>
