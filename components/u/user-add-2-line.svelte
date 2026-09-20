<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hceee5bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hceee5bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-add-2-line" {...props}></Icon>
