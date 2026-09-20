<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ai04hgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ai04hgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:time-fill" {...props}></Icon>
