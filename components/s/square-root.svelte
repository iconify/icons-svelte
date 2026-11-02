<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u66dntuxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u66dntuxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:square-root" {...props}></Icon>
