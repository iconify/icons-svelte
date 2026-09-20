<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j82ak5bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j82ak5bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sparkfun" {...props}></Icon>
