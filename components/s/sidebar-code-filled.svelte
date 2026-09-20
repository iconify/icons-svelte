<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpzp61zkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpzp61zkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sidebar-code-filled" {...props}></Icon>
