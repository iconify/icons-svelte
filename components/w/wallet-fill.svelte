<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt5mbcb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt5mbcb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wallet-fill" {...props}></Icon>
