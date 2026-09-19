<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo0pk69oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo0pk69oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:spine-24px" {...props}></Icon>
