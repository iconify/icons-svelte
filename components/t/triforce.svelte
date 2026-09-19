<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1sy0ybxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1sy0ybxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triforce" {...props}></Icon>
