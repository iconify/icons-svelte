<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udjtoqb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udjtoqb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:system76" {...props}></Icon>
