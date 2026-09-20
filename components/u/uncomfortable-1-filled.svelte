<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx0053x8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx0053x8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:uncomfortable-1-filled" {...props}></Icon>
