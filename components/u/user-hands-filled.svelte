<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkk3_lgdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkk3_lgdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-hands-filled" {...props}></Icon>
