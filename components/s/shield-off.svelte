<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps-ijm78y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps-ijm78y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:shield-off" {...props}></Icon>
