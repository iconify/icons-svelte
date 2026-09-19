<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1v6hzx8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1v6hzx8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shield-minus" {...props}></Icon>
