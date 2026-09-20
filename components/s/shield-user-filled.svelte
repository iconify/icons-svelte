<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd4eude7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hd4eude7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-user-filled" {...props}></Icon>
