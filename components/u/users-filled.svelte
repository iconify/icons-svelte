<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cahgih0ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cahgih0ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:users-filled" {...props}></Icon>
