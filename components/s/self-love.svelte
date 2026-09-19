<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiuklobge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eiuklobge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:self-love" {...props}></Icon>
