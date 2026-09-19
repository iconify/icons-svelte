<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdx3r-bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdx3r-bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:self-care-filled" {...props}></Icon>
