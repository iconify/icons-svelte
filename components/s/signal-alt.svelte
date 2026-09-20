<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8l34lwki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8l34lwki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:signal-alt" {...props}></Icon>
