<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlz7jq-ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zlz7jq-ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wood-club" {...props}></Icon>
