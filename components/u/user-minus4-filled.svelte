<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee-bfbb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee-bfbb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-minus4-filled" {...props}></Icon>
