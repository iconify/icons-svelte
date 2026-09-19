<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjprkh-wz.css';
import '../../css/e/euvix8w7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjprkh-wz"/><path class="euvix8w7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:unlock" {...props}></Icon>
