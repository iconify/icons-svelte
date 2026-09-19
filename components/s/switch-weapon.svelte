<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi6jvjypi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xi6jvjypi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:switch-weapon" {...props}></Icon>
