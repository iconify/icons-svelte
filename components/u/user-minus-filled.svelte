<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqv09lbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqv09lbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-minus-filled" {...props}></Icon>
