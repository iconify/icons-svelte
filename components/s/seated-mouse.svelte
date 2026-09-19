<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7wjn1b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7wjn1b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:seated-mouse" {...props}></Icon>
