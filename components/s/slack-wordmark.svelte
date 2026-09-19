<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apjs5gb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="apjs5gb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:slack-wordmark" {...props}></Icon>
