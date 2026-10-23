<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx6z_rr9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx6z_rr9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shell" {...props}></Icon>
