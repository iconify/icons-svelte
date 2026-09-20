<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgbb0_klj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgbb0_klj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:semrush" {...props}></Icon>
