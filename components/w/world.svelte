<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qew_s-bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qew_s-bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:world" {...props}></Icon>
