<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5-vi_78i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f5-vi_78i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spider-eye" {...props}></Icon>
