<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr7c1nblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr7c1nblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stfx" {...props}></Icon>
