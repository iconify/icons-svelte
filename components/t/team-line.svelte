<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkpzavbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkpzavbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:team-line" {...props}></Icon>
