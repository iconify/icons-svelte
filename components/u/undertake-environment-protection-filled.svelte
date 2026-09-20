<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txsqu5bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txsqu5bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:undertake-environment-protection-filled" {...props}></Icon>
