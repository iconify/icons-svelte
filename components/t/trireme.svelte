<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je_3mtapi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="je_3mtapi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trireme" {...props}></Icon>
