<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v27n-xo4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v27n-xo4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:smiling-face-fill" {...props}></Icon>
