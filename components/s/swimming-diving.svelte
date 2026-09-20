<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2e5pu1dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2e5pu1dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:swimming-diving" {...props}></Icon>
