<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozaoy9b0z.css';
import '../../css/x/xqo9p-xfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozaoy9b0z"/><path class="xqo9p-xfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-hand-up-bold" {...props}></Icon>
