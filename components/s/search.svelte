<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urath4yqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urath4yqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:search" {...props}></Icon>
