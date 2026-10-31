<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndp2m6blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndp2m6blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-letter-t" {...props}></Icon>
