<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytr-c8fjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytr-c8fjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-line" {...props}></Icon>
