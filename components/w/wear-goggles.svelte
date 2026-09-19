<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge83h09-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge83h09-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wear-goggles" {...props}></Icon>
