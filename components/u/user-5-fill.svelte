<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlc6uccsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlc6uccsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-5-fill" {...props}></Icon>
