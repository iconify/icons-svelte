<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s45ra5bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s45ra5bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:smoke-alarm" {...props}></Icon>
