<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vipnjx9wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vipnjx9wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thunder-struck" {...props}></Icon>
