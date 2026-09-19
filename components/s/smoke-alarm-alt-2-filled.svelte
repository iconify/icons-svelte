<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtscxbclt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtscxbclt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:smoke-alarm-alt-2-filled" {...props}></Icon>
