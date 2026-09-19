<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjvaiwb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fjvaiwb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:torch" {...props}></Icon>
