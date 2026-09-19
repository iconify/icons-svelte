<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjvpa0utv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjvpa0utv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wolverine-claws" {...props}></Icon>
