<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hamr9_e6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hamr9_e6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vpad" {...props}></Icon>
