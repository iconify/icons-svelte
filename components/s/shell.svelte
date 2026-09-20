<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um4-w3bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um4-w3bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shell" {...props}></Icon>
