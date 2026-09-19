<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz-oe1pab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xz-oe1pab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sailboat-filled" {...props}></Icon>
