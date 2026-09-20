<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuww48bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuww48bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sign-in-24" {...props}></Icon>
