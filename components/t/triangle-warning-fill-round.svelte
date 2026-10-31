<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftckpcdaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftckpcdaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-warning-fill-round" {...props}></Icon>
