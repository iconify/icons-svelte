<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4ch4hsgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ch4hsgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-up" {...props}></Icon>
