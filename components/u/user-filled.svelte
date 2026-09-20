<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idhh4wbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idhh4wbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-filled" {...props}></Icon>
