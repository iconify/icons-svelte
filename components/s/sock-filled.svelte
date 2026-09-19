<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnhu78nqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnhu78nqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sock-filled" {...props}></Icon>
