<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd2m22lpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd2m22lpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:th-large" {...props}></Icon>
