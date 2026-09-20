<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu9jgt3jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu9jgt3jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:terminal" {...props}></Icon>
