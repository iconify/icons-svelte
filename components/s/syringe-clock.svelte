<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klx41e55r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klx41e55r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:syringe-clock" {...props}></Icon>
