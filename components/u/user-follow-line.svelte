<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0wyz3bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0wyz3bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-follow-line" {...props}></Icon>
