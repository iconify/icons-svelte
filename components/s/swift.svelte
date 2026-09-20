<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5y3wtb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5y3wtb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:swift" {...props}></Icon>
