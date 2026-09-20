<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4ifs6byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ifs6byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:writing-sign-filled" {...props}></Icon>
