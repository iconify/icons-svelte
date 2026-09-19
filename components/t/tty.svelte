<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qswzwyq-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="qswzwyq-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tty" {...props}></Icon>
