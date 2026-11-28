<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjw-5hb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjw-5hb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-down-solid" {...props}></Icon>
