<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6_go5bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6_go5bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:turn-down" {...props}></Icon>
