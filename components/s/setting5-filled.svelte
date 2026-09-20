<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyarqnwjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyarqnwjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:setting5-filled" {...props}></Icon>
