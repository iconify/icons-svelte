<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv9whnb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv9whnb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tooth-solid" {...props}></Icon>
