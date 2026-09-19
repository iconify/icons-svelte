<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca7utaciw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca7utaciw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tetris" {...props}></Icon>
