<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf-o5jypo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lf-o5jypo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tee-pipe" {...props}></Icon>
