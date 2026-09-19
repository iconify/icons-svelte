<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_w54cc3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_w54cc3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:south-africa" {...props}></Icon>
