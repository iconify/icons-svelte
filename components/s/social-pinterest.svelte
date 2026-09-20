<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irsbxrbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irsbxrbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-pinterest" {...props}></Icon>
