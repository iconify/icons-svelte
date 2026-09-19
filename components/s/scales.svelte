<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twuct5gha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twuct5gha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scales" {...props}></Icon>
