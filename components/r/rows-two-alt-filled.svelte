<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo1kesznu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo1kesznu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rows-two-alt-filled" {...props}></Icon>
