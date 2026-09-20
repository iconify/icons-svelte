<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqe5zm-hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqe5zm-hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vip-crown-fill" {...props}></Icon>
