<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywvr6nbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywvr6nbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wash-machine-fill" {...props}></Icon>
