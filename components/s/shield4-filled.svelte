<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qayy5okhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qayy5okhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield4-filled" {...props}></Icon>
