<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqu0-5bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fqu0-5bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:xiaoyuzhou" {...props}></Icon>
