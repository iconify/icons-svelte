<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcs4o_c0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcs4o_c0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sparkles-filled" {...props}></Icon>
