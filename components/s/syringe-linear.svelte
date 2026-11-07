<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tejvvmbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tejvvmbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:syringe-linear" {...props}></Icon>
