<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf4vrq0tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf4vrq0tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:underline-fill" {...props}></Icon>
